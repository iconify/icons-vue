<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq9emnlot.css';
import '../../css/k/k70m9f-yz.css';
import '../../css/m/m4ht6ksod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mq9emnlot"/><path class="k70m9f-yz"/><path class="m4ht6ksod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kchat-light" /></template>
