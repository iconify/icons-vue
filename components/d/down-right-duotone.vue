<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5s2c3bah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5s2c3bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:down-right-duotone" /></template>
