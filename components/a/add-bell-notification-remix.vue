<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_h731ysk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p_h731ysk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:add-bell-notification-remix" /></template>
