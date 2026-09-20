<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdr4_oh2f.css';
import '../../css/k/kep5dhb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bdr4_oh2f"/><path class="kep5dhb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-illustrator" /></template>
