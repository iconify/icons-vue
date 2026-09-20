<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui5i-fbas.css';
import '../../css/r/r6cuzyb1s.css';
import '../../css/l/l_h-rg3md.css';
import '../../css/l/lt41wmb7n.css';
import '../../css/n/ne65lbbag.css';
import '../../css/d/df5n5pb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ui5i-fbas"/><path class="r6cuzyb1s"/><path class="l_h-rg3md"/><path class="lt41wmb7n"/><path class="ne65lbbag"/><path class="df5n5pb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:elasticsearch" /></template>
