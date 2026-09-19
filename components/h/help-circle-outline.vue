<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr_xxwbkp.css';
import '../../css/d/dzrft4xru.css';
import '../../css/g/g47gadbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lr_xxwbkp"/><path class="dzrft4xru"/><circle class="g47gadbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:help-circle-outline" /></template>
