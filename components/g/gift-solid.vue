<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxwi8fcof.css';
import '../../css/x/xy9vhf6wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="bxwi8fcof"/><path class="xy9vhf6wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:gift-solid" /></template>
