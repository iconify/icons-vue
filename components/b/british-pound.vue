<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akze_okwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="akze_okwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:british-pound" /></template>
