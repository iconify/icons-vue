<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu-tnl7rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:aircraft-rivet" /></template>
<style>
.iu-tnl7rn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.625 1.75h6.75q2.848 0 4.861 2.014t2.014 4.861v6.75q0 2.848-2.014 4.861t-4.861 2.014h-6.75q-2.848 0-4.861-2.014T1.75 15.375v-6.75q0-2.848 2.014-4.861T8.625 1.75m2.767 6.803q-2.413.426-2.839 2.839q-.012.072-.011.146t.018.146t.045.14q.03.068.073.128q.042.061.095.112q.054.051.116.09q.062.04.131.067t.142.04t.146.011t.146-.018t.14-.045q.068-.03.128-.073q.061-.042.112-.095q.051-.054.09-.116q.04-.062.067-.131t.04-.142q.243-1.378 1.621-1.621q.073-.013.142-.04t.131-.067t.116-.09t.095-.112q.043-.06.073-.128t.045-.14q.016-.072.018-.146t-.011-.146q-.013-.073-.04-.142t-.067-.131q-.039-.062-.09-.116q-.051-.053-.112-.095q-.06-.043-.128-.073t-.14-.045q-.072-.016-.146-.018t-.146.011");
}

</style>
