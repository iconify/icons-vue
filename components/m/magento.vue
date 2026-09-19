<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpmse0ykx.css';
import '../../css/c/c77e_usuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="rpmse0ykx"/><path class="c77e_usuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:magento" /></template>
