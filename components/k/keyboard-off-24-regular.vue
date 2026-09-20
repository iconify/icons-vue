<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxw52u7ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-off-24-regular" /></template>
<style>
.zxw52u7ja {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-2.776-2.775H4.25A2.25 2.25 0 0 1 2 16.755V7.25a2.25 2.25 0 0 1 1.96-2.23L2.22 3.28a.75.75 0 0 1 0-1.06M19.745 5a2.25 2.25 0 0 1 2.25 2.25v9.505c0 .572-.216 1.093-.568 1.49L20.36 17.18a.75.75 0 0 0 .134-.425V7.25a.75.75 0 0 0-.75-.75H9.682L8.182 5zM4.25 6.5a.75.75 0 0 0-.75.75v9.505c0 .414.336.75.75.75h12.194L14.94 16H6.75a.75.75 0 0 1-.102-1.493l.102-.007h6.69l-2.046-2.046A.998.998 0 0 1 9.504 12a1 1 0 0 1 .546-.89L5.44 6.5zM7.505 11a1 1 0 1 1 0 2a1 1 0 0 1 0-2m8.995 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2M6 8a1 1 0 1 1 0 2a1 1 0 0 1 0-2m8.995 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2m3 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2m-6 0a1 1 0 0 1 .793 1.606l-1.4-1.4A1 1 0 0 1 11.995 8");
}

</style>
