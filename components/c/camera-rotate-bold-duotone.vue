<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvnq9o5sc.css';
import '../../css/t/tfuw8dqxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvnq9o5sc"/><path class="tfuw8dqxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-rotate-bold-duotone" /></template>
