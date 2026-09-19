<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0f-scclc.css';
import '../../css/a/a-gh_pbjk.css';
import '../../css/m/me9tsg_kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t0f-scclc"/><path class="a-gh_pbjk"/><circle class="me9tsg_kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-train" /></template>
