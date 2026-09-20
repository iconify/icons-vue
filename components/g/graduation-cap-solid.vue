<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mysg7cy2i.css';
import '../../css/j/juxl4d1ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mysg7cy2i"/><path class="juxl4d1ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:graduation-cap-solid" /></template>
