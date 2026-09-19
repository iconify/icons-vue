<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik0kw2ciw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ik0kw2ciw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:face-grin-solid" /></template>
