<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srcjumbtm.css';
import '../../css/n/nsza0ub4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srcjumbtm"/><path clip-rule="evenodd" class="nsza0ub4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-add-outline" /></template>
