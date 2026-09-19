<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doe0tki7y.css';
import '../../css/m/m7pfecc5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doe0tki7y"/><path class="m7pfecc5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:badge-check" /></template>
