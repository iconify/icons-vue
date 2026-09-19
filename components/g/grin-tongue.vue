<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkga0ac_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="jkga0ac_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:grin-tongue" /></template>
