<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv7p1jn3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv7p1jn3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:archive" /></template>
