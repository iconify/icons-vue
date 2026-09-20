<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye6tf12-p.css';
import '../../css/o/o84l7ebqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye6tf12-p"/><path class="o84l7ebqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arhive-alt-small-duotone" /></template>
