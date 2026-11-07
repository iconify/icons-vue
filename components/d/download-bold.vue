<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z671n4b7f.css';
import '../../css/o/o9b3pqbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z671n4b7f"/><path class="o9b3pqbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:download-bold" /></template>
