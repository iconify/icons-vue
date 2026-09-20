<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vltle7xvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vltle7xvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:imgur" /></template>
