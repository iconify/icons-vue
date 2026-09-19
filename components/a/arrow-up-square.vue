<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh5z7f3dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lh5z7f3dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-square" /></template>
