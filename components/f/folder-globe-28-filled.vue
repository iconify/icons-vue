<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="j59hhabyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-globe-28-filled" /></template>
<style>
.j59hhabyl {
  fill: currentColor;
  d: path("M22.993 20c-.098 3.356-1.176 6-2.492 6s-2.395-2.644-2.493-6zm-5.985 0c.047 1.694.33 3.255.792 4.455a6.4 6.4 0 0 0 .596 1.197A6.5 6.5 0 0 1 14.02 20zm9.973 0a6.5 6.5 0 0 1-4.376 5.652c.233-.357.431-.765.597-1.197c.462-1.2.745-2.761.792-4.455zm-4.73-14a3.75 3.75 0 0 1 3.75 3.75v4.653A7.5 7.5 0 0 0 14.5 24H5.754a3.75 3.75 0 0 1-3.75-3.75V10.5h7.418c.73 0 1.429-.29 1.944-.806L15.06 6zm-3.855 7.348a6.4 6.4 0 0 0-.596 1.197c-.462 1.2-.745 2.761-.792 4.455H14.02a6.5 6.5 0 0 1 4.377-5.652M20.502 13c1.316 0 2.394 2.644 2.492 6h-4.985c.098-3.356 1.177-6 2.493-6m2.104.348A6.5 6.5 0 0 1 26.98 19h-2.987c-.047-1.694-.33-3.255-.792-4.455a6.4 6.4 0 0 0-.598-1.197M9.422 3c.73 0 1.429.29 1.944.806l1.884 1.883l-2.944 2.945A1.25 1.25 0 0 1 9.422 9H2V6.75A3.75 3.75 0 0 1 5.75 3z");
}

</style>
