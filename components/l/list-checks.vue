<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf22gsbmi.css';
import '../../css/h/hlcjghfxa.css';
import '../../css/q/qyt2qibcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf22gsbmi wm-a"/><path class="hlcjghfxa wm-a"/><path class="qyt2qibcp wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:list-checks" /></template>
