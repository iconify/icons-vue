<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im-34tlgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="im-34tlgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cursor-arrow-small-filled" /></template>
