<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi3ef9muv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pi3ef9muv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:diploma-outline" /></template>
