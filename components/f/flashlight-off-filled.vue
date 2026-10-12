<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7onacbub.css';
import '../../css/f/f6gjy-b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x7onacbub"/><path class="f6gjy-b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flashlight-off-filled" /></template>
