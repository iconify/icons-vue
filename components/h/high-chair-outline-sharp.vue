<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mei3p7djg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:high-chair-outline-sharp" /></template>
<style>
.mei3p7djg {
  fill: currentColor;
  d: path("m7 20l.865-9.873L6.884 4h1.894q1.206 0 2.088.777q.881.777 1.093 1.977l.45 2.862H17v1h-1.766L16.059 20h-1l-.156-1.884H8.156L8 20zM8.792 9.615h2.61l-.438-2.69q-.125-.821-.746-1.373Q9.598 5 8.777 5h-.736zm0 0h2.61zm-.538 7.5h6.544l-.233-2.75H8.493zm.317-3.75h5.916l-.258-2.75H8.823z");
}

</style>
