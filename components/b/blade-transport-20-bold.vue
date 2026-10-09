<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erstu9bfm.css';
import '../../css/z/zi8delbng.css';
import '../../css/s/sahdhwl_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="erstu9bfm"/><path class="zi8delbng"/><path class="sahdhwl_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blade-transport-20-bold" /></template>
