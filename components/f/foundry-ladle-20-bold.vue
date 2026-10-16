<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebt602b4h.css';
import '../../css/n/n_bvk3qzv.css';
import '../../css/y/yfoxxnbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ebt602b4h"/><path class="n_bvk3qzv"/><path class="yfoxxnbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:foundry-ladle-20-bold" /></template>
