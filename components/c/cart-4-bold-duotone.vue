<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj084fw9a.css';
import '../../css/x/xzn_it8jp.css';
import '../../css/b/by0-yumdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj084fw9a"/><path class="xzn_it8jp"/><path class="by0-yumdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-4-bold-duotone" /></template>
