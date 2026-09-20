<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjv3jqbyi.css';
import '../../css/q/qylci8b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cjv3jqbyi"/><path class="qylci8b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:gift-card" /></template>
