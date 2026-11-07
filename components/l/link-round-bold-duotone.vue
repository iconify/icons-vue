<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik_1hnawp.css';
import '../../css/f/fhqkw7bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ik_1hnawp"/><path class="fhqkw7bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-round-bold-duotone" /></template>
