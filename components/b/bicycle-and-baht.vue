<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_pwiya-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v_pwiya-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-and-baht" /></template>
