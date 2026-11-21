<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akdj-thul.css';
import '../../css/v/va0b3zbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akdj-thul"/><path class="va0b3zbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-fog-filled" /></template>
