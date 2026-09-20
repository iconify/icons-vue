<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4ld-7b2f.css';
import '../../css/b/b1u7f-d_l.css';
import '../../css/q/qw5i-xb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b4ld-7b2f"/><path class="b1u7f-d_l"/><path class="qw5i-xb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-satellite" /></template>
