<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqxmgob4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fqxmgob4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-right-down-20-solid" /></template>
