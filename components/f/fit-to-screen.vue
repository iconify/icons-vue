<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/extgyq5ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="extgyq5ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:fit-to-screen" /></template>
