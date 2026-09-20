<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg9i9abcg.css';
import '../../css/u/u_kzc3htk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vg9i9abcg"/><path class="u_kzc3htk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-registration" /></template>
