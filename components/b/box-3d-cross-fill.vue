<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmeeo747i.css';
import '../../css/b/bzqhk4t2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmeeo747i"/><path class="bzqhk4t2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-3d-cross-fill" /></template>
