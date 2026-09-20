<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiajmhv2g.css';
import '../../css/l/l0nhtrb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fiajmhv2g"/><path class="l0nhtrb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:app-window-bookmark-bold" /></template>
