<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/licps3vzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="licps3vzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-right-sharp" /></template>
