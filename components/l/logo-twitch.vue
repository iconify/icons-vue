<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej8uesbmu.css';
import '../../css/d/dgaovib7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ej8uesbmu"/><path class="dgaovib7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-twitch" /></template>
