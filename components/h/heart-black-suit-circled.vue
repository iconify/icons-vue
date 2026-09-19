<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e22ps333c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e22ps333c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heart-black-suit-circled" /></template>
