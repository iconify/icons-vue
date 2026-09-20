<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayvpk_rku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayvpk_rku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-wechatpay" /></template>
