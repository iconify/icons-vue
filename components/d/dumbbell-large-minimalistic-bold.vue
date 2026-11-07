<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si5z23b4a.css';
import '../../css/b/b17et-bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si5z23b4a"/><path clip-rule="evenodd" class="b17et-bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-large-minimalistic-bold" /></template>
