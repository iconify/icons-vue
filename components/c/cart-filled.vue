<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjfqssbtk.css';
import '../../css/s/sm8ol-sel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rjfqssbtk"/><path class="sm8ol-sel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:cart-filled" /></template>
