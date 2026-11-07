<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2-x-cbeh.css';
import '../../css/j/j-2a-nbrj.css';
import '../../css/o/os9vkpw9m.css';
import '../../css/y/yl0s6gb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2-x-cbeh"/><path class="j-2a-nbrj"/><path class="os9vkpw9m"/><path class="yl0s6gb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-4-bold-duotone" /></template>
