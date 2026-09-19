<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leqoybczl.css';
import '../../css/z/zx6m1cc1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leqoybczl"/><path class="zx6m1cc1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:error-alt" /></template>
