<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd2i4dbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jd2i4dbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heart-white-suit-circled-small" /></template>
