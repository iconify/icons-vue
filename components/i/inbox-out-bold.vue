<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmw0msqap.css';
import '../../css/j/jbgenzzof.css';
import '../../css/p/p09aqjb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bmw0msqap"/><path class="jbgenzzof"/><path class="p09aqjb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-out-bold" /></template>
