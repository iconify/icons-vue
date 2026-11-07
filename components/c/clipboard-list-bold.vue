<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvxlsjb-h.css';
import '../../css/y/ypgjm6kne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvxlsjb-h"/><path clip-rule="evenodd" class="ypgjm6kne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-list-bold" /></template>
