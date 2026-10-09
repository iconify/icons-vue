<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_wwqhb6k.css';
import '../../css/s/sd5b7gblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f_wwqhb6k"/><path class="sd5b7gblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:capacitor-20" /></template>
