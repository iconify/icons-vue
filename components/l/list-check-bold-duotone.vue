<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alwctsldn.css';
import '../../css/r/rjutefbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="alwctsldn"/><path class="rjutefbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-check-bold-duotone" /></template>
