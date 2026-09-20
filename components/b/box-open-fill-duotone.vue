<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxq2l9bzi.css';
import '../../css/w/w_jw7cb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxq2l9bzi"/><path clip-rule="evenodd" class="w_jw7cb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:box-open-fill-duotone" /></template>
