<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzf2slbcj.css';
import '../../css/w/w1o9hzlef.css';
import '../../css/l/lh2qbzpry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzf2slbcj wm-k"/><path class="w1o9hzlef wm-k"/><path class="lh2qbzpry wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:gold-ingot" /></template>
