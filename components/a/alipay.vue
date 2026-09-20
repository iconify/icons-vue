<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kckk9tsow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kckk9tsow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:alipay" /></template>
