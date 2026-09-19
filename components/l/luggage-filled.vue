<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atljf9blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atljf9blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:luggage-filled" /></template>
