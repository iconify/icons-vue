<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0tcmt9kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0tcmt9kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:folder-plus-fill" /></template>
