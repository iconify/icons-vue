<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knzx8abpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knzx8abpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:flashlight-on" /></template>
