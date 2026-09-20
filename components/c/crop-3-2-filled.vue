<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghwudhkpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghwudhkpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-3-2-filled" /></template>
