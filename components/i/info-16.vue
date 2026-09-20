<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o14vgl1ja.css';
import '../../css/s/s_w1wxr_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o14vgl1ja"/><path clip-rule="evenodd" class="s_w1wxr_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:info-16" /></template>
