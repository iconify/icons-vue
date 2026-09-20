<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsy1fdcdi.css';
import '../../css/c/cy43ccb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsy1fdcdi"/><path clip-rule="evenodd" class="cy43ccb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bld" /></template>
