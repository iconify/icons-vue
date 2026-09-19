<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arg7gzb5i.css';
import '../../css/q/quqfatciu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arg7gzb5i"/><path class="quqfatciu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:joystick" /></template>
