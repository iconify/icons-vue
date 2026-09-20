<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn0mf_rjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kn0mf_rjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-beside-campsite-above-campsite-beside-campsite" /></template>
