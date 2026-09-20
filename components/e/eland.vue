<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9khlybqh.css';
import '../../css/n/nnwxahb5l.css';
import '../../css/h/h091qbb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9khlybqh"/><path class="nnwxahb5l"/><path class="h091qbb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:eland" /></template>
