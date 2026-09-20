<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u77j4kbnz.css';
import '../../css/c/c-z8pxbpl.css';
import '../../css/h/hrh2fcbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u77j4kbnz"/><path clip-rule="evenodd" class="c-z8pxbpl"/><path class="hrh2fcbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:accumulator-bold-duotone" /></template>
