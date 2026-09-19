<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi2mgubtd.css';
import '../../css/f/fgk1ekbcn.css';
import '../../css/j/j0k3qqbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi2mgubtd"/><path class="fgk1ekbcn"/><path class="j0k3qqbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-id-card" /></template>
