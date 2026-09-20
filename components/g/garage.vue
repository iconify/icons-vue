<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/two3jk_np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="two3jk_np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:garage" /></template>
