<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvj8odlbj.css';
import '../../css/i/iw1lz7bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvj8odlbj"/><path class="iw1lz7bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-broken-bold-duotone" /></template>
