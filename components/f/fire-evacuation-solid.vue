<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u35a3bc9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="u35a3bc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fire-evacuation-solid" /></template>
