<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4n5wplky.css';
import '../../css/o/ow091_bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i4n5wplky"/><path class="ow091_bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:geni" /></template>
