<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_bz-sb6l.css';
import '../../css/u/ua3nsqb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_bz-sb6l"/><path class="ua3nsqb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-right-slip-filled" /></template>
