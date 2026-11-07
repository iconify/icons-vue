<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akzk_xbgp.css';
import '../../css/l/lp8u00bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akzk_xbgp"/><path clip-rule="evenodd" class="lp8u00bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bicycling-round-bold" /></template>
