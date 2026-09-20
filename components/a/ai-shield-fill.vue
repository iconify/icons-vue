<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt_dw-i0g.css';
import '../../css/t/t824cqbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt_dw-i0g"/><path clip-rule="evenodd" class="t824cqbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-shield-fill" /></template>
