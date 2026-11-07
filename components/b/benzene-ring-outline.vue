<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ugcyjie.css';
import '../../css/a/al80obcvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ugcyjie"/><path clip-rule="evenodd" class="al80obcvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:benzene-ring-outline" /></template>
