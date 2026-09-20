<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixc561o8v.css';
import '../../css/q/qrgw_-b1m.css';
import '../../css/b/bc47oi3ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixc561o8v"/><path class="qrgw_-b1m"/><path class="bc47oi3ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:duplicate-24" /></template>
