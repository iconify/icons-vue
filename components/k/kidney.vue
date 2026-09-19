<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjdzv1dwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="cjdzv1dwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:kidney" /></template>
