<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs8yq5bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hs8yq5bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:faucet-drip" /></template>
