<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btfs19cdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="btfs19cdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bug" /></template>
