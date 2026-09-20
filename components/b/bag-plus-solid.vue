<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkch5_a1m.css';
import '../../css/j/j5118ebqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gkch5_a1m"/><path clip-rule="evenodd" class="j5118ebqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bag-plus-solid" /></template>
