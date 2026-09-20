<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbrbmsbty.css';
import '../../css/v/val4s82hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="bbrbmsbty"/><path class="val4s82hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:accent" /></template>
