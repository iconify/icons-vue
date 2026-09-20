<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6yu4cbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6yu4cbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bonfire-filled" /></template>
