<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j92jx1bzk.css';
import '../../css/a/atm69obhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j92jx1bzk"/><path class="atm69obhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-open-bold-duotone" /></template>
