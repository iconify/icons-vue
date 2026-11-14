<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p51tmb6ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:balloon-weight" /></template>
<style>
.p51tmb6ey {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.88 14.166q-2.317-.361-3.734-2.284Q5.75 9.988 5.75 7.5q0-2.543 1.881-4.189Q9.415 1.75 12 1.75t4.369 1.561Q18.25 4.957 18.25 7.5q0 2.488-1.396 4.382q-1.629 2.211-4.448 2.358q-.124.398.265 1.175q.516 1.033.457 1.835h1.065q1.585-.001 2.119 1.492l.269.756q.359 1.006-.256 1.878q-.615.873-1.682.874H9.358q-1.068-.001-1.683-.874q-.615-.872-.256-1.878l.269-.755q.534-1.494 2.119-1.493h1.79q.116-.398-.268-1.165q-.544-1.087-.449-1.919");
}

</style>
