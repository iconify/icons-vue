<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc9xhebje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kc9xhebje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:circus-tent-remix" /></template>
