<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th5wqpzfa.css';
import '../../css/a/ac63k3-ur.css';
import '../../css/h/h5cwullwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="th5wqpzfa"/><path clip-rule="evenodd" class="ac63k3-ur"/><path class="h5cwullwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:desktop-check-solid" /></template>
