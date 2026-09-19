<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo7i2ob4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yo7i2ob4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:expand-solid" /></template>
