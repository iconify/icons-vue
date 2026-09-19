<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhfzghafj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":582,"height":1000};
const content = `<path class="lhfzghafj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:lock-open" /></template>
