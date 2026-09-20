<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miqaklw4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miqaklw4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-align-middle-filled" /></template>
