<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xig3ipb1f.css';
import '../../css/k/kh0mfynvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xig3ipb1f"/><path class="kh0mfynvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:envelopes-o" /></template>
