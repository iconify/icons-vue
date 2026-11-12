<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_8s107tv.css';
import '../../css/e/e8df_acjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_8s107tv"/><path class="e8df_acjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:docs-collaboration" /></template>
