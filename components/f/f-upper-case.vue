<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac_v2wbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":455,"height":735};
const content = `<path class="ac_v2wbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:f-upper-case" /></template>
