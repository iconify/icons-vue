<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahhfo8gsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahhfo8gsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:add-friends-outlined" /></template>
