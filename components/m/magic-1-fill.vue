<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omv53s5os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="omv53s5os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:magic-1-fill" /></template>
