<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wemig523u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wemig523u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:hash-24" /></template>
