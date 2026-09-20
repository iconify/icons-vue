<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhwamkbws.css';
import '../../css/o/ox3sqx-4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhwamkbws"/><path class="ox3sqx-4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-arrow-down-duotone" /></template>
