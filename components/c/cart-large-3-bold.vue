<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvyfd2cnm.css';
import '../../css/v/vs5n4kb4o.css';
import '../../css/p/ppziiibjw.css';
import '../../css/t/txahl3bke.css';
import '../../css/d/dspe7mbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvyfd2cnm"/><path class="vs5n4kb4o"/><path class="ppziiibjw"/><path class="txahl3bke"/><path class="dspe7mbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-large-3-bold" /></template>
