<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnra-dbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mnra-dbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fear" /></template>
