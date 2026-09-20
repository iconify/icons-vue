<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqx49sbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqx49sbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-swiss-franc-sharp-fill" /></template>
