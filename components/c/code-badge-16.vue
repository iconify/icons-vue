<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv2r58bup.css';
import '../../css/k/k0khjcc8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lv2r58bup"/><path class="k0khjcc8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:code-badge-16" /></template>
