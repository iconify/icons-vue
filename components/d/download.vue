<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uswc0fr3j.css';
import '../../css/n/nu8i0-bfz.css';
import '../../css/d/dqe_68bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uswc0fr3j wm-k"/><path class="nu8i0-bfz wm-a"/><path class="dqe_68bhs wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:download" /></template>
