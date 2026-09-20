<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik-i4x10n.css';
import '../../css/c/chowghc9o.css';
import '../../css/s/s9kf_ac-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik-i4x10n"/><path class="chowghc9o"/><path class="s9kf_ac-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:balance-duotone" /></template>
