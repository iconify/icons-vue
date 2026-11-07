<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghfixm1dc.css';
import '../../css/q/qii6rvmzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghfixm1dc"/><path class="qii6rvmzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copyright-bold-duotone" /></template>
